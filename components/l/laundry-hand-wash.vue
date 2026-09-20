<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/n/n7u4o-vzj.css';
import '../../css/l/lqjiyubml.css';
import '../../css/o/o-fe66dks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="n7u4o-vzj"/><path class="lqjiyubml"/><path class="o-fe66dks"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:laundry-hand-wash" /></template>

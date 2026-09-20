<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xpj4vkbbe.css';
import '../../css/l/lohd83bha.css';
import '../../css/r/rpk44qb5q.css';
import '../../css/o/ouzjljbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xpj4vkbbe"/><path class="lohd83bha"/><path class="rpk44qb5q"/><path class="ouzjljbfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:android-settings" /></template>

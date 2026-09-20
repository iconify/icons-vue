<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/o/opo1zcc8y.css';
import '../../css/o/o8cb350vf.css';
import '../../css/e/em4i2mbry.css';
import '../../css/a/am077nbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="opo1zcc8y"/><path class="o8cb350vf"/><path class="em4i2mbry"/><path class="am077nbxd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:app-window-link" /></template>

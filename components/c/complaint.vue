<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/o/oagawgbbv.css';
import '../../css/o/olpgfdb0y.css';
import '../../css/o/olyxe4bhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oagawgbbv"/><path class="olpgfdb0y"/><path class="olyxe4bhs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:complaint" /></template>

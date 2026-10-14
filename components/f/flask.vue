<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/m/mmhfqtz0e.css';
import '../../css/w/w4rw20y0k.css';
import '../../css/i/ijue4lwmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="mmhfqtz0e"/><path class="w4rw20y0k"/><path class="ijue4lwmp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:flask" /></template>

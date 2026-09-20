<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6tjmo3jk.css';
import '../../css/g/gj7luzv3t.css';
import '../../css/b/bv8e12z1q.css';
import '../../css/d/dv8xrgbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="z6tjmo3jk"><path class="gj7luzv3t"/><path class="bv8e12z1q"/><path class="dv8xrgbwr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:guitar" /></template>

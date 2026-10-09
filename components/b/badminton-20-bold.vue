<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp8tavb-f.css';
import '../../css/v/vuh460n8o.css';
import '../../css/f/f78t3-62r.css';
import '../../css/r/r4kug05-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fp8tavb-f"/><path class="vuh460n8o"/><path class="f78t3-62r"/><path class="r4kug05-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:badminton-20-bold" /></template>

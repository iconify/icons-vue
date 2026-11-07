<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lineszbmd.css';
import '../../css/y/yp3yidbbi.css';
import '../../css/i/iuq7zmbfp.css';
import '../../css/u/udl63nbzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lineszbmd"/><path class="yp3yidbbi"/><path class="iuq7zmbfp"/><path class="udl63nbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:case-round-bold" /></template>

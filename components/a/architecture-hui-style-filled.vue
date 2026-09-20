<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy_9-78me.css';
import '../../css/k/kmix8d4jl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sy_9-78me"/><path class="kmix8d4jl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:architecture-hui-style-filled" /></template>

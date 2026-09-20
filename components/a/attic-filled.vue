<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egngdtb-a.css';
import '../../css/k/kmix8d4jl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egngdtb-a"/><path class="kmix8d4jl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:attic-filled" /></template>

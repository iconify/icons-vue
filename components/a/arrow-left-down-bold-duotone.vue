<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm99dfc3e.css';
import '../../css/c/cvyd4hdhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tm99dfc3e"/><path class="cvyd4hdhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-left-down-bold-duotone" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0gg5hi1k.css';
import '../../css/d/d25mwn3tm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0gg5hi1k"/><path clip-rule="evenodd" class="d25mwn3tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-minus-outline" /></template>

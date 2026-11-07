<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4lfqkpls.css';
import '../../css/p/pzmtr-buq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4lfqkpls"/><path clip-rule="evenodd" class="pzmtr-buq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-up-outline" /></template>

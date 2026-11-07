<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8fbprehd.css';
import '../../css/u/u_bgapr5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8fbprehd"/><path clip-rule="evenodd" class="u_bgapr5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-cog-bold" /></template>

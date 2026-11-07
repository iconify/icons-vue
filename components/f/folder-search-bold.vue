<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5dxyelor.css';
import '../../css/f/f03p8tb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5dxyelor"/><path clip-rule="evenodd" class="f03p8tb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-search-bold" /></template>

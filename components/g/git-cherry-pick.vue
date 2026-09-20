<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbsp2pyyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbsp2pyyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:git-cherry-pick" /></template>

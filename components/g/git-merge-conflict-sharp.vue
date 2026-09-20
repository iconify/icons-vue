<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnmbmdbyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnmbmdbyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-merge-conflict-sharp" /></template>

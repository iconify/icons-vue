<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_lhvpb9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":488};
const content = `<path class="u_lhvpb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:grooveshark" /></template>

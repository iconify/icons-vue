<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tap2fcboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tap2fcboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:align-right-outline" /></template>

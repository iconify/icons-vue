<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1k9bac8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s1k9bac8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-checkmark-circle" /></template>

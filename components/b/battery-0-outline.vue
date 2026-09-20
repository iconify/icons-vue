<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sngn-6bwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sngn-6bwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:battery-0-outline" /></template>

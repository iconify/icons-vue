<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eoue0ptya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eoue0ptya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:logo-foursquare" /></template>

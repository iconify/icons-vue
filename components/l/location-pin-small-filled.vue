<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g60hnciii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="g60hnciii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:location-pin-small-filled" /></template>

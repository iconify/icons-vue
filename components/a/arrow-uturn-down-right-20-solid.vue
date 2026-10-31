<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcpvqfk3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="pcpvqfk3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-uturn-down-right-20-solid" /></template>

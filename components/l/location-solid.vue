<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkkpyin0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="jkkpyin0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:location-solid" /></template>

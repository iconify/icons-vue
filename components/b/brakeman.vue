<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v67dzhjys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":334,"height":512};
const content = `<path class="v67dzhjys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:brakeman" /></template>

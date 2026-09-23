<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nin0wu0rp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nin0wu0rp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:escape" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du3re5bnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="du3re5bnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:chevron-right-md" /></template>

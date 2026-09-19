<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-awxjc1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-awxjc1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:arrow-up-solid" /></template>

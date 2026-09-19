<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3f7l6b0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3f7l6b0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:flag-solid" /></template>

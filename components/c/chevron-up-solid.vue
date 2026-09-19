<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2-u_vb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2-u_vb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:chevron-up-solid" /></template>

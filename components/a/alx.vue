<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi2iq4b2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pi2iq4b2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:alx" /></template>

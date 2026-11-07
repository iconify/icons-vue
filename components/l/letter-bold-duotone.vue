<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxyrlcb9h.css';
import '../../css/a/avjg2qbrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxyrlcb9h"/><path class="avjg2qbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:letter-bold-duotone" /></template>

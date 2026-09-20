<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqnp09b_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqnp09b_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:less" /></template>

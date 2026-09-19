<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go288nbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="go288nbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:heated-maiden" /></template>

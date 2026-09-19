<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9rjmmfqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9rjmmfqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:duplicati" /></template>

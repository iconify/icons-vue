<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frce2ob2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frce2ob2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:exclamation-24" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1mhh7bie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1mhh7bie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bracket-arrow-left-sharp" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnp-6j6hh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lnp-6j6hh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:clearformatting" /></template>

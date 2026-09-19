<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk4jnibns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="uk4jnibns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:laugh-beam" /></template>

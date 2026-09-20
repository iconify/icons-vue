<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxqwbu3yg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rxqwbu3yg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ephemera-dark" /></template>

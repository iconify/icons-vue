<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivs3jibks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":1024};
const content = `<path class="ivs3jibks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:calendarthree" /></template>

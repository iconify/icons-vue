<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7fzjqbhc.css';
import '../../css/d/drnzv18qw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y7fzjqbhc"/><path class="drnzv18qw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:gift" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufhls85tg.css';
import '../../css/c/c6xz9rq9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ufhls85tg"/><path class="c6xz9rq9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:connectwise-screenconnect-dark" /></template>

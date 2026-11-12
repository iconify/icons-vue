<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi9cg7bus.css';
import '../../css/c/c6xz9rq9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bi9cg7bus"/><path class="c6xz9rq9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:connectwise-screenconnect-dark" /></template>

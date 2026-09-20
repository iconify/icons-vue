<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df-4nqnau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="df-4nqnau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ikuai" /></template>

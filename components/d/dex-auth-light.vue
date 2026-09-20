<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwckj7bep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rwckj7bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dex-auth-light" /></template>

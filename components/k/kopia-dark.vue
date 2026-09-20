<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqj-v0bmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mqj-v0bmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kopia-dark" /></template>

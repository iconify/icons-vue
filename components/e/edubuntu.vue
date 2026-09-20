<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgfplbbgp.css';
import '../../css/g/gsi1lc1zm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kgfplbbgp"/><path class="gsi1lc1zm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:edubuntu" /></template>

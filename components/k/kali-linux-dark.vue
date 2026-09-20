<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_jbxs31n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a_jbxs31n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kali-linux-dark" /></template>

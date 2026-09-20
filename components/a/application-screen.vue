<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b58k86k9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b58k86k9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:application-screen" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9t4mnboc.css';
import '../../css/f/fr1kxcbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r9t4mnboc"/><path class="fr1kxcbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cloudflare-zero-trust-dark" /></template>

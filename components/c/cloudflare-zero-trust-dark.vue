<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxmb1c0no.css';
import '../../css/f/fr1kxcbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lxmb1c0no"/><path class="fr1kxcbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cloudflare-zero-trust-dark" /></template>

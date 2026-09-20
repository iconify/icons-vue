<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjcj41b6z.css';
import '../../css/l/l-n55zbgm.css';
import '../../css/a/a79pf1bey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pjcj41b6z"/><path class="l-n55zbgm"/><path class="a79pf1bey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-docs" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/foflm7r3e.css';
import '../../css/t/tlq2fkbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="foflm7r3e"/><path class="tlq2fkbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:coinmarketcap-blue" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn-2fcubd.css';
import '../../css/c/cia5ouwnr.css';
import '../../css/v/vu75sh_8v.css';
import '../../css/a/a5ynwdbbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bn-2fcubd"/><path class="cia5ouwnr"/><path class="vu75sh_8v"/><path class="a5ynwdbbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ente-auth-light" /></template>

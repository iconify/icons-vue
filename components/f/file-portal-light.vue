<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irsl63llt.css';
import '../../css/s/sbw6ahqto.css';
import '../../css/m/m8tny2bgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="irsl63llt"/><path class="sbw6ahqto"/><path class="m8tny2bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:file-portal-light" /></template>

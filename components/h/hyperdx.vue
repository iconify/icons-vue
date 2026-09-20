<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7_p-eb5l.css';
import '../../css/l/lx1hlcb1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t7_p-eb5l"/><path class="lx1hlcb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hyperdx" /></template>

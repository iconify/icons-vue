<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psqwx_-ti.css';
import '../../css/i/if85crc2z.css';
import '../../css/m/mc-ix1blr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="psqwx_-ti"/><path class="if85crc2z"/><path class="mc-ix1blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hardcover-dark" /></template>

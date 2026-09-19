<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxzshjbvd.css';
import '../../css/p/pd4mgccgx.css';
import '../../css/o/oqp24fb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lxzshjbvd"/><path class="pd4mgccgx"/><path class="oqp24fb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-cube" /></template>

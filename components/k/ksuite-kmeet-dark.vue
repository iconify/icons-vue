<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ueyhp9s-v.css';
import '../../css/u/u323u8bnq.css';
import '../../css/c/cdjzimb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ueyhp9s-v"/><path class="u323u8bnq"/><path class="cdjzimb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-kmeet-dark" /></template>

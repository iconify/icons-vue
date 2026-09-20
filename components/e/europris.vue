<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi7d7k0gf.css';
import '../../css/h/hk4vhieox.css';
import '../../css/o/o5pdp4q-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="vi7d7k0gf"/><path class="hk4vhieox"/><path class="o5pdp4q-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:europris" /></template>

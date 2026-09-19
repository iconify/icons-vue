<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc4s4wbdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="lc4s4wbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:haproxy" /></template>

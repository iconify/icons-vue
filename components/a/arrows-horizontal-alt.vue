<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/f/fkvl2c.css';
import '../../css/k/k_e22n.css';
import '../../css/s/so-from-14.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c fkvl2c"/><path class="a0m25c k_e22n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:arrows-horizontal-alt" /></template>

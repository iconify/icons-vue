<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvmpzpbvf.css';
import '../../css/v/vqmwm_bhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvmpzpbvf"/><path class="vqmwm_bhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:eye-24" /></template>

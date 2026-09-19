<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixn_89u5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixn_89u5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:assist-listening" /></template>

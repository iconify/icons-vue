<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n100ldbyg.css';
import '../../css/g/gzw5n1b6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n100ldbyg"/><path class="gzw5n1b6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:desktop-solid" /></template>

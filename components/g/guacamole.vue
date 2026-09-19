<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quhpgf8oq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="quhpgf8oq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:guacamole" /></template>

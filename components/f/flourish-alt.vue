<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go2yq50ts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="go2yq50ts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:flourish-alt" /></template>

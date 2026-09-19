<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_0hn4skk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_0hn4skk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:lock-open-alt-01-filled" /></template>

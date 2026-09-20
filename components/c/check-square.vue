<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cicrr7b6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cicrr7b6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:check-square" /></template>

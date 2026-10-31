<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh2693boa.css';
import '../../css/v/vlyhmq5ak.css';
import '../../css/g/gkjkb4bue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="lh2693boa"/><path class="vlyhmq5ak"/><path class="gkjkb4bue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:jamaica" /></template>

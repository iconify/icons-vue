<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/miazw5f2j.css';
import '../../css/n/n1xy6nh9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="miazw5f2j"/><circle class="n1xy6nh9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-compass" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbw6oqbwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbw6oqbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:firewall" /></template>

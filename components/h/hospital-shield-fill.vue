<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6pf4lbun.css';
import '../../css/r/rqbyrwbza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6pf4lbun"/><path class="rqbyrwbza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:hospital-shield-fill" /></template>

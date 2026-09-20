<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sucysfikq.css';
import '../../css/r/rifcqzbni.css';
import '../../css/n/nigjfvbya.css';
import '../../css/i/ibgenzjqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="sucysfikq"/><path class="rifcqzbni"/><path class="nigjfvbya"/><path class="ibgenzjqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-gift-shop" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcn3ptbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcn3ptbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:lamp-charge-filled" /></template>

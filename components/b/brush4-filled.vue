<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hab5lhbhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hab5lhbhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:brush4-filled" /></template>

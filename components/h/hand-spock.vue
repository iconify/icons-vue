<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjlsmmzwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="rjlsmmzwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:hand-spock" /></template>

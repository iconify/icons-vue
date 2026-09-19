<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnzo3sbiw.css';
import '../../css/z/zfws45ina.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jnzo3sbiw"/><circle class="zfws45ina"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:location-outline" /></template>

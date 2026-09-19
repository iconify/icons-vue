<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prcy1udmo.css';
import '../../css/j/jnlj8ybtf.css';
import '../../css/j/jn0obg5tf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="prcy1udmo"/><ellipse class="jnlj8ybtf"/><path class="jn0obg5tf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:flashlight-sharp" /></template>

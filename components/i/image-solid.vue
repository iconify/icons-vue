<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blhnusbed.css';
import '../../css/j/joyp_jpja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="blhnusbed"/><path clip-rule="evenodd" class="joyp_jpja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:image-solid" /></template>

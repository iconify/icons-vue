<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfj8c45tf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfj8c45tf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:license-off" /></template>

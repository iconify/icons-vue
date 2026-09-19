<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvvpg1bae.css';
import '../../css/o/o2fnn15tf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvvpg1bae"/><path class="o2fnn15tf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:hashtag-outline" /></template>

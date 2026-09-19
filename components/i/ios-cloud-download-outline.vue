<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a66vcju6v.css';
import '../../css/j/jb9r22v3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a66vcju6v"/><path class="jb9r22v3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-cloud-download-outline" /></template>

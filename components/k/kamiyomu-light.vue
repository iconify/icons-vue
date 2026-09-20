<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p73-vbb6z.css';
import '../../css/z/z6eui5bmf.css';
import '../../css/k/k7xjikbow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p73-vbb6z"/><path class="z6eui5bmf"/><path class="k7xjikbow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kamiyomu-light" /></template>

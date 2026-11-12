<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyun3dd4z.css';
import '../../css/h/hfnpruahq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lyun3dd4z"/><path class="hfnpruahq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amazon-s3-light" /></template>

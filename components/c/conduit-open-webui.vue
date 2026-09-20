<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2_7wmb7u.css';
import '../../css/w/wdiw5pb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o2_7wmb7u"/><path class="wdiw5pb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:conduit-open-webui" /></template>

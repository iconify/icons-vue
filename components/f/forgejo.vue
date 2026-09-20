<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kejaeac3h.css';
import '../../css/s/sbbfclb0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kejaeac3h"/><path class="sbbfclb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:forgejo" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl5abcb0s.css';
import '../../css/k/k3ds82w0c.css';
import '../../css/e/ebf9xob5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gl5abcb0s"/><path class="k3ds82w0c"/><path class="ebf9xob5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:capacitor-runtime-light" /></template>

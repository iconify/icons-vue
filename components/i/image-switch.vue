<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm5zddb2t.css';
import '../../css/v/vcti67wgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qm5zddb2t"/><path class="vcti67wgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:image-switch" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9cl-boot.css';
import '../../css/a/apvpf298a.css';
import '../../css/b/bjo519b-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="l9cl-boot"/><path class="apvpf298a"/><path class="bjo519b-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:italy" /></template>

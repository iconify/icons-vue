<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv0ihtbqe.css';
import '../../css/p/p06tfrbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gv0ihtbqe"/><path clip-rule="evenodd" class="p06tfrbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:contract-solid" /></template>

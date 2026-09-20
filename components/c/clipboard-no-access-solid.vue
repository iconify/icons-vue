<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txy8rw54j.css';
import '../../css/c/cix5zfqeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="txy8rw54j"/><path clip-rule="evenodd" class="cix5zfqeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:clipboard-no-access-solid" /></template>

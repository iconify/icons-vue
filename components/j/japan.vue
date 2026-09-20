<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7x5h9bzy.css';
import '../../css/r/rvjkfln8h.css';
import '../../css/s/snp287xku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s7x5h9bzy"/><path class="rvjkfln8h"/><path class="snp287xku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-emojis:japan" /></template>

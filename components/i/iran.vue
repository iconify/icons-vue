<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1x_6zbkv.css';
import '../../css/s/s22y7z9os.css';
import '../../css/y/yhov8zbzn.css';
import '../../css/d/dyfumibih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="d1x_6zbkv"/><path class="s22y7z9os"/><path class="yhov8zbzn"/><path class="dyfumibih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:iran" /></template>

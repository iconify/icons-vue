<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlw9nms0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:azm-outline-rounded" /></template>
<style>
.zlw9nms0k {
  fill: currentColor;
  d: path("M12.372 19.224q-.378.378-.875.17T11 18.652v-5.036q0-.27-.173-.443T10.385 13H5.347q-.534 0-.742-.497t.17-.875l6.148-6.148q.218-.219.519-.35t.632-.13h5.31q.666 0 1.14.475T19 6.615v5.31q0 .332-.13.632t-.35.52zm3.128-9.34v4.791l2.5-2.5v-5.56q0-.269-.173-.442T17.385 6h-5.56l-2.5 2.5h4.79q.589 0 .987.398t.398.987m-3.5 3.5v4.79l2.5-2.5v-5.56q0-.269-.173-.442t-.442-.173h-5.56l-2.5 2.5h4.79q.589 0 .987.398t.398.987");
}

</style>

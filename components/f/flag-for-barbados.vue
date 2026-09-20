<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="nyu_gja2t"/><path class="wlozsacri"/><path class="m3iw_ubqc"/><path class="yngayub7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-barbados" /></template>
<style>
.m3iw_ubqc {
  fill: var(--svg-color--ffc726, #FFC726);
  d: path("M12 5h12v26H12z");
}

.nyu_gja2t {
  fill: var(--svg-color--00267f, #00267F);
  d: path("M36 27a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4v18z");
}

.wlozsacri {
  fill: var(--svg-color--00267f, #00267F);
  d: path("M4 5a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h8V5H4z");
}

.yngayub7e {
  d: path("M22.83 13.516c-1.406 0-2.5 1.031-2.859 1.438c.422-.094.516.234.453.438c-.444 1.477-.819 3.215-.931 4.15h-.903v-5.186l1.09-.226l-1.366-.273l-.283-1.377l-.283 1.377l-1.367.273l1.1.228v5.184h-.947c-.112-.936-.487-2.674-.931-4.15c-.062-.203.031-.531.453-.438c-.359-.406-1.453-1.438-2.859-1.438c.613.906 2.245 3.432 2.458 6.403v.622h1.826v2.414h1.109v-2.414h1.756v-.232c.085-3.14 1.844-5.848 2.484-6.793z");
  fill: var(--svg-color--000, #000);
}

</style>

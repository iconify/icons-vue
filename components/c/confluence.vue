<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":246};
const content = `<defs><linearGradient id="SVGvnhR7dox" x1="99.14%" x2="33.859%" y1="112.708%" y2="37.755%"><stop offset="18%" class="sav6x4bmf"/><stop offset="100%" class="g_gp7lgqe"/></linearGradient><linearGradient id="SVGgker3cTp" x1=".926%" x2="66.18%" y1="-12.582%" y2="62.306%"><stop offset="18%" class="sav6x4bmf"/><stop offset="100%" class="g_gp7lgqe"/></linearGradient></defs><path fill="url(#SVGvnhR7dox)" class="zzsqhf5tt"/><path fill="url(#SVGgker3cTp)" class="uuqoz0z0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:confluence" /></template>
<style>
.g_gp7lgqe {
  stop-color: var(--svg-color--2684ff, #2684ff);
}

.sav6x4bmf {
  stop-color: var(--svg-color--0052cc, #0052cc);
}

.uuqoz0z0t {
  d: path("M246.115 58.232c2.641-4.307 5.607-9.305 8.127-13.287a8.127 8.127 0 0 0-2.723-11.052L198.696 1.386a8.127 8.127 0 0 0-11.58 2.682c-2.113 3.535-4.835 8.127-7.802 13.043c-20.926 34.538-41.974 30.313-79.925 12.19L47.176 4.515a8.127 8.127 0 0 0-10.93 4.063L11.093 65.465a8.127 8.127 0 0 0 4.063 10.645c11.052 5.202 33.035 15.563 52.823 25.112c71.351 34.538 131.854 32.222 178.135-42.99");
}

.zzsqhf5tt {
  d: path("M9.26 187.33c-2.64 4.307-5.607 9.305-8.126 13.287a8.127 8.127 0 0 0 2.722 11.052l52.823 32.507a8.127 8.127 0 0 0 11.256-2.763c2.113-3.536 4.835-8.127 7.801-13.044c20.926-34.538 41.974-30.312 79.925-12.19l52.376 24.908a8.127 8.127 0 0 0 10.93-4.063l25.152-56.886a8.127 8.127 0 0 0-4.063-10.646c-11.052-5.201-33.034-15.562-52.823-25.111c-71.189-34.579-131.691-32.344-177.972 42.949");
}

</style>

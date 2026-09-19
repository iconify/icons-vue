<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="gz5kd0hrf"><path class="qscudmb-r"/><path class="oibjvj64p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:busts-in-silhouette" /></template>
<style>
.gz5kd0hrf {
  fill: var(--svg-color--5d6d74, #5d6d74);
}

.oibjvj64p {
  d: path("M34.5 19.9c1.8 2 3.8 5.5 3.7 11c.7.5 1.3 1.4 1.5 2.8c.4 2.6-.7 6.8-4 8.1c-.9 2.1-1.9 3.7-3 4.6H62s-.3-2.7-1-4.3c-.3-.6-14.2-8.9-14.2-8.9c-2-1.4-2.2-2.8-.6-3.6c1.4-.7 2.5-2.9 3.4-5.3c.2.1.3.1.5 0c3.7-1.1 3.8-8.5 1.3-7.2C53.7-2.6 27-3 28.1 15.9c2.5.7 4.7 2 6.4 4");
}

.qscudmb-r {
  d: path("M45.5 57.7c-.3-.6-14.2-8.9-14.2-8.9c-2-1.4-2.2-2.8-.6-3.7c1.4-.7 2.5-2.9 3.4-5.3c.2.1.3.1.5 0c3.7-1.1 3.8-8.5 1.3-7.2c2.3-20.1-25.6-20.2-23.3 0c-2.5-1.3-2.4 6.1 1.3 7.2h.5c.9 2.4 2 4.6 3.4 5.3c1.6.8 1.3 2.1-.7 3.7c-.6.5-9.6 5.5-12.2 7.2c-1 .7-1.8 1.3-1.9 1.6c-.7 1.7-1 4.4-1 4.4h44.4s-.2-2.7-.9-4.3");
}

</style>

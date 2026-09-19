<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="fgdqa7l0a"/><path class="ol93lr87e"/><path class="n50g81b2t"/><g class="hq2-vcghy"><path class="hn4pyndam"/><path class="u6dqjh8-c"/></g><path class="n3s-f2bve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-tuvalu" /></template>
<style>
.fgdqa7l0a {
  fill: var(--svg-color--2a5f9e, #2a5f9e);
  d: path("M12 12h21v21H12z");
}

.hn4pyndam {
  d: path("M15.4 14L30 32h2v-4.9L21.4 14z");
}

.hq2-vcghy {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
}

.n3s-f2bve {
  fill: var(--svg-color--ffe62e, #ffe62e);
  d: path("m28.9 50.2l-.6-2.1l-.7 2.1h-2.2l1.8 1.2l-.7 2.1l1.8-1.3l1.7 1.3l-.7-2.1l1.8-1.2zm8.9-1.6l.6-2.1l-1.7 1.3l-1.7-1.3l.6 2.1l-1.7 1.2H36l.7 2.1l.7-2.1h2.1zm.6-9.3l-1.7 1.3l-1.7-1.3l.6 2l-1.7 1.3H36l.7 2.1l.7-2.1h2.1l-1.7-1.3zm6.8 7.4l.7-2l-1.8 1.3l-1.7-1.3l.7 2l-1.8 1.3h2.2l.6 2l.7-2H47zm-1.7-14.4l.6 2l.7-2H47L45.2 31l.7-2l-1.8 1.3l-1.7-1.3l.7 2l-1.8 1.3zm6.2 8.9l-.7-2l-.6 2h-2.2l1.7 1.3l-.6 2l1.7-1.2l1.8 1.2l-.7-2l1.7-1.3zm0-11l.7 2l.7-2h2.1l-1.7-1.3l.7-2.1l-1.8 1.3l-1.7-1.3l.6 2.1l-1.7 1.3zm6.3 7l-.7-2.1l-.7 2.1h-2.1l1.7 1.2l-.6 2.1l1.7-1.3l1.8 1.3l-.7-2.1l1.7-1.2zm-1.8-12.6l-.6 2l1.7-1.2l1.8 1.2l-.7-2l1.7-1.3H56l-.7-2l-.7 2h-2.1z");
}

.n50g81b2t {
  fill: var(--svg-color--fff, #fff);
  d: path("M32 2c-4.7 0-9.1 1.1-13.1 3v6H11v7.9H5c-1.9 4-3 8.4-3 13.1h12V17l12 15h6v-7.5L23.6 14H32z");
}

.ol93lr87e {
  fill: var(--svg-color--5b97b1, #5b97b1);
  d: path("M32 2v30H2c0 16.6 13.4 30 30 30s30-13.4 30-30S48.6 2 32 2");
}

.u6dqjh8-c {
  d: path("M32 5H18.9c-6 2.9-11 7.9-13.9 13.9V32h6V11h21z");
}

</style>

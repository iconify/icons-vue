<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="e8wmjdbnv"/><path class="mqb0jyiwd"/><path class="ce8a3yjlo"/><path class="wkizb2blu"/><path class="gwal58b5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:boy-medium-dark-skin-tone" /></template>
<style>
.ce8a3yjlo {
  fill: var(--svg-color--60352a, #60352a);
  d: path("M12 22a1 1 0 0 1-1-1v-2a1 1 0 0 1 2 0v2a1 1 0 0 1-1 1m12 0a1 1 0 0 1-1-1v-2a1 1 0 1 1 2 0v2a1 1 0 0 1-1 1");
}

.e8wmjdbnv {
  fill: var(--svg-color--af7e57, #af7e57);
  d: path("M6 20c0 2.209-1.119 4-2.5 4S1 22.209 1 20s1.119-4 2.5-4S6 17.791 6 20m29 0c0 2.209-1.119 4-2.5 4S30 22.209 30 20s1.119-4 2.5-4s2.5 1.791 2.5 4");
}

.gwal58b5f {
  fill: var(--svg-color--60352a, #60352a);
  d: path("M18 .354C8.77.354 3 6.816 3 12.2s1.154 7.539 2.308 5.385l2.308-4.308s3.791-.124 6.099-2.278c0 0-1.071 4 6.594.124c0 0-.166 3.876 5.191-.124c0 0 4.039 1.201 5.191 6.586c.32 1.494 2.309 0 2.309-5.385S28.385.354 18 .354");
}

.mqb0jyiwd {
  fill: var(--svg-color--af7e57, #af7e57);
  d: path("M4 20.562c0-8.526 6.268-15.438 14-15.438s14 6.912 14 15.438S25.732 35 18 35S4 29.088 4 20.562");
}

.wkizb2blu {
  fill: var(--svg-color--915a34, #915a34);
  d: path("M18 30c-4.188 0-6.357-1.06-6.447-1.105a1 1 0 0 1 .89-1.791c.051.024 1.925.896 5.557.896c3.665 0 5.54-.888 5.559-.897a1.003 1.003 0 0 1 1.336.457a.997.997 0 0 1-.447 1.335C24.356 28.94 22.188 30 18 30m1-5h-2a1 1 0 1 1 0-2h2a1 1 0 1 1 0 2");
}

</style>

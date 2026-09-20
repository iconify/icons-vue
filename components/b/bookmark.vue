<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="lxzfvybzd"/><path class="jqepxtbpd"/><path class="b1sbsfbxi"/><path class="bqoxbbb5p"/><path class="i7ziitb3r"/><path class="vq-bxib5c"/><g class="sdcfnj7sm"><path class="z--82dbui"/><path class="ato6ufzge"/></g><path class="ul25vphdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:bookmark" /></template>
<style>
.ato6ufzge {
  d: path("M25 28a1 1 0 0 1-.832-.445L21 22.803l-3.168 4.752A.998.998 0 0 1 16 27V4a1 1 0 0 1 1-1h8a1 1 0 0 1 1 1v23a1 1 0 0 1-1 1m-4-8c.334 0 .646.167.832.445L24 23.697V5h-6v18.697l2.168-3.252c.186-.278.498-.445.832-.445");
}

.b1sbsfbxi {
  fill: var(--svg-color--fff, #fff);
  d: path("M31 31a3 3 0 0 1-3 3H4a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h24a3 3 0 0 1 3 3z");
}

.bqoxbbb5p {
  fill: var(--svg-color--aab8c2, #aab8c2);
  d: path("M31 32a4 4 0 0 1-4 4H6a4 4 0 0 1-4-4V10a4 4 0 0 1 4-4h21a4 4 0 0 1 4 4z");
}

.i7ziitb3r {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M29 32a4 4 0 0 1-4 4H6a4 4 0 0 1-4-4V12a4 4 0 0 1 4-4h19.335C27.544 8 29 9.456 29 11.665z");
}

.jqepxtbpd {
  fill: var(--svg-color--f5f8fa, #f5f8fa);
  d: path("M33 30a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4V6c0-4.119-.021-4 5-4h21a4 4 0 0 1 4 4z");
}

.lxzfvybzd {
  fill: var(--svg-color--aab8c2, #aab8c2);
  d: path("M35 26a4 4 0 0 1-4 4H5a4 4 0 0 1-4-4V6.313C1 4.104 6.791 0 9 0h20.625C32.719 0 35 2.312 35 5.375z");
}

.sdcfnj7sm {
  fill: var(--svg-color--dd2e44, #dd2e44);
}

.ul25vphdc {
  fill: var(--svg-color--f5f8fa, #f5f8fa);
  d: path("M15 2h12v2H15z");
}

.vq-bxib5c {
  fill: var(--svg-color--aab8c2, #aab8c2);
  d: path("M6 6C4.312 6 4.269 4.078 5 3.25C5.832 2.309 7.125 2 9.438 2H11V0H8.281C4.312 0 1 2.5 1 5.375V32a4 4 0 0 0 4 4h2V6z");
}

.z--82dbui {
  d: path("M17 4v23l4-6l4 6V4z");
}

</style>

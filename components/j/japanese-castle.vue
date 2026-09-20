<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="eno60hbmb"/><path class="s7q_kcbun"/><path class="ciuajmb5t"/><path class="w96x8gbdd"/><path class="jthmk_s9f"/><path class="gblsxsbkq"/><path class="t8tlfeb0r"/><path class="iaki7pbmq"/><path class="n7k5g0q8q"/><path class="gs_ojkb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:japanese-castle" /></template>
<style>
.ciuajmb5t {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M30 20H6l-5 4h34z");
}

.eno60hbmb {
  fill: var(--svg-color--d1d3d4, #d1d3d4);
  d: path("M5 23h26v7H5z");
}

.gblsxsbkq {
  fill: var(--svg-color--d1d3d4, #d1d3d4);
  d: path("M6 17h24v3H6zm18-8V5H12v4h-2v2h16V9z");
}

.gs_ojkb4y {
  fill: var(--svg-color--6d6e71, #6d6e71);
  d: path("M5 27h26v2H5z");
}

.iaki7pbmq {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M23 0v1H13V0h-1v2h12V0z");
}

.jthmk_s9f {
  fill: var(--svg-color--66757f, #66757f);
  d: path("m30 14l-1-5H7l-1 5l-4 3h32zM18 9.882L26.236 14H9.764z");
}

.n7k5g0q8q {
  fill: var(--svg-color--66757f, #66757f);
  d: path("m30 14.764l-5.105-2.553l-6-3L18 8.764l-.895.447l-6 3L6 14.764V16h24zM12 14l6-3l6 3z");
}

.s7q_kcbun {
  fill: var(--svg-color--d99e82, #d99e82);
  d: path("M0 36h36l-4-7H4z");
}

.t8tlfeb0r {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M12 2h12v2l2 2H10l2-2z");
}

.w96x8gbdd {
  fill: var(--svg-color--d1d3d4, #d1d3d4);
  d: path("M18 9.882L9.764 14h16.472z");
}

</style>

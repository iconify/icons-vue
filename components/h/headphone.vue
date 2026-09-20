<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="o2lh2sb_f"/><path class="k_2kwnygd"/><path class="gsv1jzi0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:headphone" /></template>
<style>
.gsv1jzi0u {
  fill: var(--svg-color--55acee, #55acee);
  d: path("m19.182 10.016l-6.364 1.313c-.45.093-.818.544-.818 1.004v16.185a6.2 6.2 0 0 0-2.087-.36c-2.785 0-5.042 1.755-5.042 3.922c0 2.165 2.258 3.827 5.042 3.827C12.649 35.905 14.922 34 15 32V16.39l4.204-.872c.449-.093.796-.545.796-1.004v-3.832c0-.458-.368-.759-.818-.666m8 3.151l-4.297.865c-.45.093-.885.544-.885 1.003V26.44c0-.152-.878-.24-1.4-.24c-2.024 0-3.633 1.276-3.633 2.852c0 1.574 1.658 2.851 3.683 2.851s3.677-1.277 3.677-2.851l-.014-11.286l2.869-.598c.45-.093.818-.544.818-1.003v-2.33c0-.459-.368-.76-.818-.668");
}

.k_2kwnygd {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M6 27a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2v-9a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2zm30 0a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2v-9a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2z");
}

.o2lh2sb_f {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M18 0C9.716 0 3 6.716 3 15v9h3v-9C6 8 11.269 2.812 18 2.812S30 8 30 15v10l3-1v-9c0-8.284-6.716-15-15-15");
}

</style>
